<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlt5h_mac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dlt5h_mac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ear-listen" {...props}></Icon>
