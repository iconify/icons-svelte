<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5a82gbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e5a82gbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:arrowheads-up" {...props}></Icon>
