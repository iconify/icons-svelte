<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4p-8x6bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4p-8x6bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:badminton-line" {...props}></Icon>
