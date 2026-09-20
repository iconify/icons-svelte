<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxzcx_yab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cxzcx_yab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pyshelf" {...props}></Icon>
