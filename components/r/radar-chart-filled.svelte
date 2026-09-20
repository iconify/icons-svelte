<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulcxtvz6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ulcxtvz6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:radar-chart-filled" {...props}></Icon>
