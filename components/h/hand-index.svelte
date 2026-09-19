<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yrmnrrt6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yrmnrrt6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:hand-index" {...props}></Icon>
