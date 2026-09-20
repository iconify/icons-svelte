<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wztl4rbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="wztl4rbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:bar-11" {...props}></Icon>
