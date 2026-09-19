<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4u2r3x1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d4u2r3x1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:archive-arrow-down" {...props}></Icon>
