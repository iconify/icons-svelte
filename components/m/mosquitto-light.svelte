<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cesziac5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cesziac5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mosquitto-light" {...props}></Icon>
