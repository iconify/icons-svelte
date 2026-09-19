<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cap4h-y1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="cap4h-y1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-outline" {...props}></Icon>
