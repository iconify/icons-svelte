<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xedtc1bcc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xedtc1bcc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-hypper-dark" {...props}></Icon>
