<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pg2cq_bng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pg2cq_bng"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:flaresolverr-dark" {...props}></Icon>
