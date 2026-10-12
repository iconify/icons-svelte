<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuwyr7tqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tuwyr7tqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-circle-code-filled" {...props}></Icon>
