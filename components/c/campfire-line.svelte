<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk4w6bctl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk4w6bctl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:campfire-line" {...props}></Icon>
