<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi3xz7l2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oi3xz7l2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:bed-2-line" {...props}></Icon>
