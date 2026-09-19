<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elmbf2wzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="elmbf2wzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:cli-bold" {...props}></Icon>
