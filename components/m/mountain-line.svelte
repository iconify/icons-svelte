<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq8k30bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tq8k30bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mountain-line" {...props}></Icon>
