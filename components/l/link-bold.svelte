<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrw8ww-qi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="yrw8ww-qi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:link-bold" {...props}></Icon>
