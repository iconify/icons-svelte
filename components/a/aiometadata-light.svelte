<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc_9f5b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hc_9f5b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:aiometadata-light" {...props}></Icon>
