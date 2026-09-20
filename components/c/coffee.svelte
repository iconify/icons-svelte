<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cq1py1b7q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cq1py1b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:coffee" {...props}></Icon>
