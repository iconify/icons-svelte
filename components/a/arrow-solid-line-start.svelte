<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9oya2dhl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="m9oya2dhl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-line-start" {...props}></Icon>
