<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i4jtddqdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i4jtddqdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:circle-parking-off-line" {...props}></Icon>
