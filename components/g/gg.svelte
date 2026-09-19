<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1f9li6sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p1f9li6sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:gg" {...props}></Icon>
