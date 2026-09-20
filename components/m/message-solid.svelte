<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwp_ibcvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rwp_ibcvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-solid" {...props}></Icon>
