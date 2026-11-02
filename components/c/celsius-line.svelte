<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryf94lbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryf94lbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:celsius-line" {...props}></Icon>
