<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldjj17z3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ldjj17z3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:garage-and-key" {...props}></Icon>
