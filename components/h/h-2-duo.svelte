<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-ow4s4hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="s-ow4s4hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:h-2-duo" {...props}></Icon>
