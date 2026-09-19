<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrk_kpbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zrk_kpbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:notebook-template" {...props}></Icon>
