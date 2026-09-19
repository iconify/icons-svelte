<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2bqm2ptp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s2bqm2ptp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-recording" {...props}></Icon>
