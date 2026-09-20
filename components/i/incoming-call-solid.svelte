<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3vpn-b5r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p3vpn-b5r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:incoming-call-solid" {...props}></Icon>
