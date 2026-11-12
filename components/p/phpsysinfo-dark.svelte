<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iivk5q4jp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iivk5q4jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpsysinfo-dark" {...props}></Icon>
