<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqqlw_b6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="rqqlw_b6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:eight" {...props}></Icon>
