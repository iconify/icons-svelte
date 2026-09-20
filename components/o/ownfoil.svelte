<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6b09o61e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w6b09o61e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ownfoil" {...props}></Icon>
