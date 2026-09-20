<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5_w49avu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p5_w49avu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:mail-send-email-message-circle-solid" {...props}></Icon>
