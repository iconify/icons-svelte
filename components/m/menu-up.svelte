<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whztoynct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="whztoynct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:menu-up" {...props}></Icon>
