<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvu1ubcpn.css';
import '../../css/p/po8pqxbxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bvu1ubcpn"/><path class="po8pqxbxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:rescript-interface" {...props}></Icon>
