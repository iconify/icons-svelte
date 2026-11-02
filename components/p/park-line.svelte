<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w606y1h7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w606y1h7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:park-line" {...props}></Icon>
