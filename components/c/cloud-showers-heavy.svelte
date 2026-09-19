<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw-xedbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yw-xedbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud-showers-heavy" {...props}></Icon>
