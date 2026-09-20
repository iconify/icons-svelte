<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ludt5vszz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ludt5vszz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-two-bubbles-oval-solid" {...props}></Icon>
