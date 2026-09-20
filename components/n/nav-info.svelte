<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8u56tb3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e8u56tb3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-info" {...props}></Icon>
