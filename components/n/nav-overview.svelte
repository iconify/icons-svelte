<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yna26d0th.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yna26d0th"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-overview" {...props}></Icon>
