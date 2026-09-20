<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8ttspegr.css';
import '../../css/v/v2yh4c2xt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="u8ttspegr"/><path class="v2yh4c2xt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:raising-hands" {...props}></Icon>
