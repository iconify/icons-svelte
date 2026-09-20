<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqtb8fbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqtb8fbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:call-forwarding-outgoing-1" {...props}></Icon>
