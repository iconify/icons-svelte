<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t97dd4xnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t97dd4xnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bell-dot-round" {...props}></Icon>
