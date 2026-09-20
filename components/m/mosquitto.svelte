<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz0w159ze.css';
import '../../css/k/k5b4rgmdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iz0w159ze"/><path class="k5b4rgmdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:mosquitto" {...props}></Icon>
