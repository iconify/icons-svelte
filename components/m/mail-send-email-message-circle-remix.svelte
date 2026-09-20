<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lv376j6xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lv376j6xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:mail-send-email-message-circle-remix" {...props}></Icon>
