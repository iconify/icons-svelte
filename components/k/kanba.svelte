<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxv007l0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nxv007l0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kanba" {...props}></Icon>
