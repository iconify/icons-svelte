<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxnxqlq1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pxnxqlq1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:rollup-js" {...props}></Icon>
