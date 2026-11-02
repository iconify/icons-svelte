<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0w-x3_1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0w-x3_1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:apple-intelligence-line" {...props}></Icon>
