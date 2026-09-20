<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij9jytbwz.css';
import '../../css/r/rk9vncbpu.css';
import '../../css/w/wswcn9beg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ij9jytbwz"/><path class="rk9vncbpu"/><path class="wswcn9beg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:conversation-question-warning-3" {...props}></Icon>
