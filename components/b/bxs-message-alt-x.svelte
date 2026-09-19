<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9_0x6oon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9_0x6oon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-alt-x" {...props}></Icon>
