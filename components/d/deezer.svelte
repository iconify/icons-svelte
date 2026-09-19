<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgsx5cf1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fgsx5cf1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:deezer" {...props}></Icon>
