<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfpn6w7ca.css';
import '../../css/i/ifnhtt1oc.css';
import '../../css/n/ndygbv4bu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfpn6w7ca"/><path clip-rule="evenodd" class="ifnhtt1oc"/><path clip-rule="evenodd" class="ndygbv4bu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-quote-bold-duotone" {...props}></Icon>
