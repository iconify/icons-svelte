<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpmc3ybxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="mpmc3ybxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:note-pad-1" {...props}></Icon>
