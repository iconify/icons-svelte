<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ggulujbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ggulujbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jstor-light" {...props}></Icon>
