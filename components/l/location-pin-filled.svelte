<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvp_25qpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qvp_25qpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:location-pin-filled" {...props}></Icon>
