<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clvq9sbjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clvq9sbjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-info-filled" {...props}></Icon>
