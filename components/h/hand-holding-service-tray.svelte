<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c97p5ln2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c97p5ln2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:hand-holding-service-tray" {...props}></Icon>
