<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko2r1eq8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ko2r1eq8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:f-bold" {...props}></Icon>
