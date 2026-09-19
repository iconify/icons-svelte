<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo7iwkb_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<rect class="wo7iwkb_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rectangle-duo" {...props}></Icon>
