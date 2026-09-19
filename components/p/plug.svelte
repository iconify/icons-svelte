<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cptk9ebxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="cptk9ebxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:plug" {...props}></Icon>
