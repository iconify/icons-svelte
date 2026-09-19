<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlb28h91q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tlb28h91q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-pause" {...props}></Icon>
