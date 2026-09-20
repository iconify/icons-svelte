<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgv7ffjnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mgv7ffjnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openhands-dark" {...props}></Icon>
