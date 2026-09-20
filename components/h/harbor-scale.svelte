<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wza49-blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wza49-blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:harbor-scale" {...props}></Icon>
