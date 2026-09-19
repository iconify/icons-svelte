<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw0_rhs8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1536};
const content = `<path class="xw0_rhs8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cc-paypal" {...props}></Icon>
