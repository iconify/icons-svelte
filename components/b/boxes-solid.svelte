<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgn1o77jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xgn1o77jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:boxes-solid" {...props}></Icon>
