<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt52jcc3i.css';
import '../../css/n/ns2y_7_hd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rt52jcc3i"/><path class="ns2y_7_hd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-pricetags" {...props}></Icon>
