<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwu--hqpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="rwu--hqpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:exclamation-triangle-bold" {...props}></Icon>
