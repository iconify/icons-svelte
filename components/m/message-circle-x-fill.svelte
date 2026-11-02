<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir1mvbvgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ir1mvbvgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-circle-x-fill" {...props}></Icon>
