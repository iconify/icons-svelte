<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdp-fub5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdp-fub5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:cloud-cancel-outline" {...props}></Icon>
