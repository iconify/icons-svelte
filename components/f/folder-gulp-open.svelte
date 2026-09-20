<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v702yrfnr.css';
import '../../css/n/nfgrvkl1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v702yrfnr"/><path class="nfgrvkl1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-gulp-open" {...props}></Icon>
