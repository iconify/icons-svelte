<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2wu7f5cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2wu7f5cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rename" {...props}></Icon>
