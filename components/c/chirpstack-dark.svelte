<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwqnu2b7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fwqnu2b7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chirpstack-dark" {...props}></Icon>
