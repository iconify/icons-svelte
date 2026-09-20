<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2v5bx4nc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t2v5bx4nc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:propane-tank" {...props}></Icon>
