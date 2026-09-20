<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hofbyd45q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hofbyd45q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:needle-and-spool" {...props}></Icon>
