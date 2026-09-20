<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6ok2rj4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q6ok2rj4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-bubble-typing-oval-solid" {...props}></Icon>
