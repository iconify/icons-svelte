<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8g050_hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h8g050_hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linuxserver-io-light" {...props}></Icon>
