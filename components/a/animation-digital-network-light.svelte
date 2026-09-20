<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wiyct_b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wiyct_b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:animation-digital-network-light" {...props}></Icon>
