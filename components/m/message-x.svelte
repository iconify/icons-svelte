<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st61j9bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st61j9bfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-x" {...props}></Icon>
