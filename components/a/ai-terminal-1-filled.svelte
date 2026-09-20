<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu65qx2xi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu65qx2xi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ai-terminal-1-filled" {...props}></Icon>
