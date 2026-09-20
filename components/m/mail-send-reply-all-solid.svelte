<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnylftb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dnylftb1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-send-reply-all-solid" {...props}></Icon>
