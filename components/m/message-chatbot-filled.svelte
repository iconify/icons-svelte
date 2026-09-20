<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdh9vvbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdh9vvbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-chatbot-filled" {...props}></Icon>
