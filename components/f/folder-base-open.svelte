<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uj-tnhbad.css';
import '../../css/x/x9f5z-bmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uj-tnhbad"/><path class="x9f5z-bmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-base-open" {...props}></Icon>
