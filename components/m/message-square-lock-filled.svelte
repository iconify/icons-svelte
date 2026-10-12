<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq20y-biq.css';
import '../../css/y/yv4alofav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq20y-biq"/><path clip-rule="evenodd" class="yv4alofav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-lock-filled" {...props}></Icon>
