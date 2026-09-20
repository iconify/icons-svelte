<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yp_7a8bjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yp_7a8bjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:fountain-14" {...props}></Icon>
