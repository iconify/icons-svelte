<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3yz9_bjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p3yz9_bjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:monero-dark" {...props}></Icon>
