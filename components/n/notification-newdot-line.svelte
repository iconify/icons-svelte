<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b11lcybfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b11lcybfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:notification-newdot-line" {...props}></Icon>
