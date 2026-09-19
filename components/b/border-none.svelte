<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ay90zkbwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ay90zkbwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:border-none" {...props}></Icon>
