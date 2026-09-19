<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnwo8kn8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="xnwo8kn8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:l-bold" {...props}></Icon>
