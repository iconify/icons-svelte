<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pe0-zvsab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="pe0-zvsab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:map-marker-duo" {...props}></Icon>
