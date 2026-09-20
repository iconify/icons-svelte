<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydol1y82a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ydol1y82a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ownfoil-light" {...props}></Icon>
