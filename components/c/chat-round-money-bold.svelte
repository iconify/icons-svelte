<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5da1fblt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w5da1fblt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-round-money-bold" {...props}></Icon>
