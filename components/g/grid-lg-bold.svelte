<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpuz_ibvb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="dpuz_ibvb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-lg-bold" {...props}></Icon>
