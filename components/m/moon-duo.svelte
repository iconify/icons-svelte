<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_wtfcbbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="w_wtfcbbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:moon-duo" {...props}></Icon>
