<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te17cbcvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te17cbcvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-to-down-line" {...props}></Icon>
