<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwj331l_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uwj331l_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:book-check-line" {...props}></Icon>
