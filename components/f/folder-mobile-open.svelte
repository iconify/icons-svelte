<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v702yrfnr.css';
import '../../css/p/pzyrpx0do.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v702yrfnr"/><path class="pzyrpx0do"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mobile-open" {...props}></Icon>
