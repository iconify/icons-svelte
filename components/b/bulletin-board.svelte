<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lj8mc-72s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lj8mc-72s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:bulletin-board" {...props}></Icon>
