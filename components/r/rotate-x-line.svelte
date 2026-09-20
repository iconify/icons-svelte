<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luj5q1c5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luj5q1c5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rotate-x-line" {...props}></Icon>
