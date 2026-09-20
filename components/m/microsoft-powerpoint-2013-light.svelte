<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9vw_m5_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y9vw_m5_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-2013-light" {...props}></Icon>
