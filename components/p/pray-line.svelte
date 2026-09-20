<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eu8xl2y1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eu8xl2y1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pray-line" {...props}></Icon>
