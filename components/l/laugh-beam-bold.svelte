<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1mxsq6ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="n1mxsq6ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:laugh-beam-bold" {...props}></Icon>
