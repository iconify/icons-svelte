<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtvj1dvjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="gtvj1dvjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-send-email-send-email-paper-airplane" {...props}></Icon>
