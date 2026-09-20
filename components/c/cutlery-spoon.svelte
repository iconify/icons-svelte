<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poig4bcxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="poig4bcxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cutlery-spoon" {...props}></Icon>
