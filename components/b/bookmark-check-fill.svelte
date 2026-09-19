<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl1rlvb2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zl1rlvb2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bookmark-check-fill" {...props}></Icon>
