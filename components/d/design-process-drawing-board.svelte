<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytj7at_sk.css';
import '../../css/b/b4ouy7bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ytj7at_sk"/><path class="b4ouy7bdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:design-process-drawing-board" {...props}></Icon>
