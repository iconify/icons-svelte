<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7wx_cblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d7wx_cblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:123-stroke-16" {...props}></Icon>
