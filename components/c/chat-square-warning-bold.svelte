<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q0xsmyu0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q0xsmyu0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chat-square-warning-bold" {...props}></Icon>
