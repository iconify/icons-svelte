<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jczlzlbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jczlzlbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-bar-2-line" {...props}></Icon>
