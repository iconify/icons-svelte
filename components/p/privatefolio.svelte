<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvf5h20sn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yvf5h20sn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:privatefolio" {...props}></Icon>
