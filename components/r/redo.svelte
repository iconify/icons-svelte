<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd50cvy7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qd50cvy7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codex:redo" {...props}></Icon>
