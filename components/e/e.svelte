<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmsizop1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="lmsizop1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:e" {...props}></Icon>
