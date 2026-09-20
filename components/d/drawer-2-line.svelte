<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmldzsb8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zmldzsb8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drawer-2-line" {...props}></Icon>
