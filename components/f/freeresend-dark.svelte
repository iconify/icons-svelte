<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p90yc2h1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p90yc2h1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:freeresend-dark" {...props}></Icon>
