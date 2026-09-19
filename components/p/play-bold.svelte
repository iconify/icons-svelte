<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aneo2yrwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="aneo2yrwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:play-bold" {...props}></Icon>
