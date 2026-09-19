<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj4vyycmp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="fj4vyycmp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:check-bold" {...props}></Icon>
