<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rwieclb2b.css';
import '../../css/i/i26zuu1we.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rwieclb2b"/><path class="i26zuu1we"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:beer-off-filled" {...props}></Icon>
