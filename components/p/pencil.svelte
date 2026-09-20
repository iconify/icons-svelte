<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yakvasj5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yakvasj5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:pencil" {...props}></Icon>
