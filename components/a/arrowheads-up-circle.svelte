<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3xn8u7bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o3xn8u7bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-up-circle" {...props}></Icon>
