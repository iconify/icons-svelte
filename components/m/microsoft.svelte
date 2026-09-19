<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e-n7bi8nq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e-n7bi8nq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:microsoft" {...props}></Icon>
