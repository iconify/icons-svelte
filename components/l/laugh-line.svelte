<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uin8x9ouj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uin8x9ouj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:laugh-line" {...props}></Icon>
