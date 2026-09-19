<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6e58ubjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a6e58ubjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:border-none-bold" {...props}></Icon>
