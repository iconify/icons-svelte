<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wve-dxbgv.css';
import '../../css/i/ixz4scd6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wve-dxbgv"/><path class="ixz4scd6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-mercurial" {...props}></Icon>
