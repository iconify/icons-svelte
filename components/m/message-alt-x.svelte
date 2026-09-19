<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rrrju3b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rrrju3b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-alt-x" {...props}></Icon>
