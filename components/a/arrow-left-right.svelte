<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrvn9ab9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zrvn9ab9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-right" {...props}></Icon>
