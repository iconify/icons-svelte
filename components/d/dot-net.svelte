<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1fz6zbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1fz6zbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dot-net" {...props}></Icon>
