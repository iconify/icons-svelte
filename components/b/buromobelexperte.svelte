<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nw1ycublj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nw1ycublj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:buromobelexperte" {...props}></Icon>
