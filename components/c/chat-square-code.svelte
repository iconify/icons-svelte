<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruu_5mhlg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ruu_5mhlg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chat-square-code" {...props}></Icon>
