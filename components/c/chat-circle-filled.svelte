<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lp5yahbch.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lp5yahbch"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chat-circle-filled" {...props}></Icon>
