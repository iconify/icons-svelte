<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4xbjs1xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="w4xbjs1xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:liberapay" {...props}></Icon>
