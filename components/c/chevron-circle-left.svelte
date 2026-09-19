<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xc_60jfce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xc_60jfce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:chevron-circle-left" {...props}></Icon>
