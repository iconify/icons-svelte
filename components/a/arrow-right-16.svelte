<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lmm9cxber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lmm9cxber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-right-16" {...props}></Icon>
