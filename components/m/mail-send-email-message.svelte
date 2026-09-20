<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl7oi3wqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wl7oi3wqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-send-email-message" {...props}></Icon>
