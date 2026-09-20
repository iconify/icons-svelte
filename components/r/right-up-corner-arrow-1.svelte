<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fqdbfbchb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fqdbfbchb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:right-up-corner-arrow-1" {...props}></Icon>
