<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4y--i39e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="u4y--i39e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:ci-cd-line" {...props}></Icon>
