<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g4gc-vbgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="g4gc-vbgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heading-duo" {...props}></Icon>
