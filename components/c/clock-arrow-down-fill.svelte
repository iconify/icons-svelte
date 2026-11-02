<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imky4xyfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imky4xyfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:clock-arrow-down-fill" {...props}></Icon>
