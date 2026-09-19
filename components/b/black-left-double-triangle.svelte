<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb902yrex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="zb902yrex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:black-left-double-triangle" {...props}></Icon>
