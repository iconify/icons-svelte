<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfg0owgcl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="hfg0owgcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:music-list" {...props}></Icon>
