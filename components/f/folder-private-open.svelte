<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v702yrfnr.css';
import '../../css/q/qp9anacag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v702yrfnr"/><path class="qp9anacag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-private-open" {...props}></Icon>
