<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqa3f49xb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="qqa3f49xb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bezier-pentagon" {...props}></Icon>
