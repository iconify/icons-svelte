<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg0_fpbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xg0_fpbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ackify-light" {...props}></Icon>
