<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a33rtejtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path class="a33rtejtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:activity-1-outline" {...props}></Icon>
