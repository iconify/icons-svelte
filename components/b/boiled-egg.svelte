<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqd-lj30l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":512};
const content = `<path class="uqd-lj30l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:boiled-egg" {...props}></Icon>
