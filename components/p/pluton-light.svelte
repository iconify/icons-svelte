<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wbpngy_pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wbpngy_pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:pluton-light" {...props}></Icon>
