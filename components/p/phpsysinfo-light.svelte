<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npbkuw6op.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npbkuw6op"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:phpsysinfo-light" {...props}></Icon>
