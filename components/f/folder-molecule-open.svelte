<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv8-lrn5y.css';
import '../../css/d/dt86ds9dv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xv8-lrn5y"/><path class="dt86ds9dv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-molecule-open" {...props}></Icon>
