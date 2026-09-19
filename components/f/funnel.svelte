<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4z3rxh1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l4z3rxh1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:funnel" {...props}></Icon>
