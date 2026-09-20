<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv8-lrn5y.css';
import '../../css/l/la8zlpbmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xv8-lrn5y"/><path class="la8zlpbmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-messages-open" {...props}></Icon>
