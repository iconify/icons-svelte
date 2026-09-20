<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1s8c0b-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s1s8c0b-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:chat-bubble-square-block-solid" {...props}></Icon>
