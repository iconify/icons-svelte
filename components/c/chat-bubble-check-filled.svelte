<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvq26cl9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvq26cl9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-bubble-check-filled" {...props}></Icon>
