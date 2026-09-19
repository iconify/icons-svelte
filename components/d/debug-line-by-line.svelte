<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0l5uqr_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k0l5uqr_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-line-by-line" {...props}></Icon>
