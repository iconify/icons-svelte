<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l24zkvows.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="l24zkvows"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:drag-horizontal" {...props}></Icon>
