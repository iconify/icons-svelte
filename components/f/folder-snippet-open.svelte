<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv8-lrn5y.css';
import '../../css/u/uohrmebri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xv8-lrn5y"/><path class="uohrmebri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-snippet-open" {...props}></Icon>
