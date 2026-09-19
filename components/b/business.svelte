<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4e79wb0p.css';
import '../../css/m/myrkvvb4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4e79wb0p"/><path class="myrkvvb4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:business" {...props}></Icon>
