<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn1r1dbvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="wn1r1dbvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:d-pad-bold" {...props}></Icon>
