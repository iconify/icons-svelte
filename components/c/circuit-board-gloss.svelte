<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq-0zab1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qq-0zab1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circuit-board-gloss" {...props}></Icon>
