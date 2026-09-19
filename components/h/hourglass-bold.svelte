<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cik2l7bjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cik2l7bjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-bold" {...props}></Icon>
