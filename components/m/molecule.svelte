<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq6p72bht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq6p72bht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:molecule" {...props}></Icon>
