<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpmmq_k7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dpmmq_k7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fireshare-dark" {...props}></Icon>
