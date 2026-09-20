<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwgmc0e6k.css';
import '../../css/i/ipamtibyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hwgmc0e6k"/><path class="ipamtibyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:invoke-ai" {...props}></Icon>
