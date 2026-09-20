<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3sqb0ytu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v3sqb0ytu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-bubble-crack-square-remix" {...props}></Icon>
