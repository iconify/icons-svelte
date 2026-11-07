<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfpn6w7ca.css';
import '../../css/d/d3_iiz01o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfpn6w7ca"/><path class="d3_iiz01o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-add-bold-duotone" {...props}></Icon>
