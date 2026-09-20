<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tt6bjmk9e.css';
import '../../css/e/e77jw6bhj.css';
import '../../css/m/m-0u4sbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tt6bjmk9e"/><path class="e77jw6bhj"/><path class="m-0u4sbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:grain" {...props}></Icon>
