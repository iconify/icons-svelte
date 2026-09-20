<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad1b9_ipc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ad1b9_ipc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:mail-send-envelope-solid" {...props}></Icon>
