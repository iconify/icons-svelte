<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te6448bsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te6448bsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:camcorder-3-fill" {...props}></Icon>
