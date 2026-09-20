<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qq3tpwbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qq3tpwbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-right-circle" {...props}></Icon>
