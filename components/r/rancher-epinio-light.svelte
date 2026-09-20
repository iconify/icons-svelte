<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lta_4qb-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lta_4qb-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rancher-epinio-light" {...props}></Icon>
