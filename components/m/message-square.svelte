<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xux3b0vgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xux3b0vgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-square" {...props}></Icon>
