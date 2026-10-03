<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrdmjfb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rrdmjfb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:haproxy-cluster-manager-light" {...props}></Icon>
