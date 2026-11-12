<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts3lanhek.css';
import '../../css/m/mlhjt3b1y.css';
import '../../css/b/bri9cxbwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ts3lanhek"/><path class="mlhjt3b1y"/><path class="bri9cxbwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dawarich" {...props}></Icon>
