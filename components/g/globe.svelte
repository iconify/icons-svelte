<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt-7v1wio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xt-7v1wio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:globe" {...props}></Icon>
