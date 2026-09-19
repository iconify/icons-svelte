<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tna52mbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tna52mbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:d" {...props}></Icon>
