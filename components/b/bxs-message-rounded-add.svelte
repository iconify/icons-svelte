<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vylacab7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vylacab7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-rounded-add" {...props}></Icon>
