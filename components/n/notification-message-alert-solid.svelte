<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrj_-3b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="qrj_-3b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:notification-message-alert-solid" {...props}></Icon>
