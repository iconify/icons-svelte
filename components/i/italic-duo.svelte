<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/esb1j89to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="esb1j89to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:italic-duo" {...props}></Icon>
