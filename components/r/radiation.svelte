<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe9q7uw-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fe9q7uw-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:radiation" {...props}></Icon>
