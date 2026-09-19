<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ll7kddc1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="ll7kddc1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:four" {...props}></Icon>
