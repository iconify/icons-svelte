<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-71aubjb.css';
import '../../css/d/dmusveb8u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h-71aubjb"/><path class="dmusveb8u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:readarr-radarr-light" {...props}></Icon>
