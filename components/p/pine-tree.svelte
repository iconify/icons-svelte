<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl2-b5b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl2-b5b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pine-tree" {...props}></Icon>
