<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wef_rfbrt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wef_rfbrt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:file-braces-corner" {...props}></Icon>
