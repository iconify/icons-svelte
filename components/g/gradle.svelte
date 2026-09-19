<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clsdao61r.css';
import '../../css/j/j-h21xgaa.css';
import '../../css/o/osrapabyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="clsdao61r"><path class="j-h21xgaa"/><path class="osrapabyl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:gradle" {...props}></Icon>
