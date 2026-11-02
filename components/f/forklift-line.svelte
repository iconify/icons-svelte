<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5q_egfpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5q_egfpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:forklift-line" {...props}></Icon>
