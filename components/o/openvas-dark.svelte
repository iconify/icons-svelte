<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f1mxp-b2u.css';
import '../../css/j/jw8pkbh0s.css';
import '../../css/w/wn29amz4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f1mxp-b2u"/><path class="jw8pkbh0s"/><path class="wn29amz4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openvas-dark" {...props}></Icon>
