<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6d3kbcdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6d3kbcdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:christmas-tree-filled" {...props}></Icon>
