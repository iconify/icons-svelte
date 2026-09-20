<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb8m4hn8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="tb8m4hn8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:qr-code-solid" {...props}></Icon>
