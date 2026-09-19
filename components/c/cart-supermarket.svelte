<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvtgyfbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":496};
const content = `<path class="dvtgyfbov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cart-supermarket" {...props}></Icon>
