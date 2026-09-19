<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n14n-3bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="n14n-3bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:angle-duo" {...props}></Icon>
