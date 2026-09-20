<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fg_q-fb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fg_q-fb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-up-left-stipple-inner" {...props}></Icon>
