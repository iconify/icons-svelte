<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkmf4y6fo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="tkmf4y6fo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:landmark-1" {...props}></Icon>
