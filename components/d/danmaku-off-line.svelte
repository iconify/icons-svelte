<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2j9q7g2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2j9q7g2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:danmaku-off-line" {...props}></Icon>
