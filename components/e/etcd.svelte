<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjs49zbtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vjs49zbtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:etcd" {...props}></Icon>
