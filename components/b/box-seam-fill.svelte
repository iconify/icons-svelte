<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqq1ptbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cqq1ptbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:box-seam-fill" {...props}></Icon>
