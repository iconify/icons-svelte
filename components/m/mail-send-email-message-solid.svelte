<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uecvhybxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uecvhybxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-send-email-message-solid" {...props}></Icon>
