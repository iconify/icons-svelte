<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyj0pr4wr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyj0pr4wr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:diamond-2-line" {...props}></Icon>
