<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qf557bbty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qf557bbty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-dashed-fill" {...props}></Icon>
