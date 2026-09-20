<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usbuiebgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="usbuiebgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:creative-commons-by" {...props}></Icon>
