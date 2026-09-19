<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x05pc-vgk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="x05pc-vgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:arpdown" {...props}></Icon>
