<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7ppq1bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="t7ppq1bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:plugin-16" {...props}></Icon>
