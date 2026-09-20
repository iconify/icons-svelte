<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5z--lbqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p5z--lbqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fahrenheit-line" {...props}></Icon>
