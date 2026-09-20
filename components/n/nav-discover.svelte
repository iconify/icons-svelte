<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckxrjp7pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ckxrjp7pe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:nav-discover" {...props}></Icon>
