<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzyvr_bnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rzyvr_bnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:bars-offset" {...props}></Icon>
