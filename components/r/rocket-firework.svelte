<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7ogqu_4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j7ogqu_4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:rocket-firework" {...props}></Icon>
