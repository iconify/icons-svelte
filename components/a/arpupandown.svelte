<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bigywb2mm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="bigywb2mm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:arpupandown" {...props}></Icon>
