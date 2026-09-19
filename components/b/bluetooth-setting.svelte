<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q5h8h31za.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":272,"height":512};
const content = `<path class="q5h8h31za"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:bluetooth-setting" {...props}></Icon>
