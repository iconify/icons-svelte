<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctg0mn-rs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ctg0mn-rs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:mail-send-reply-all-flat" {...props}></Icon>
