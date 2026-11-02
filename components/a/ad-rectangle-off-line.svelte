<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjk_lmb7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rjk_lmb7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ad-rectangle-off-line" {...props}></Icon>
