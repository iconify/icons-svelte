<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpg_nd5bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jpg_nd5bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-text-filled" {...props}></Icon>
