<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd1yx_bjk.css';
import '../../css/c/cl9xofbwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kd1yx_bjk"/><path class="cl9xofbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-go" {...props}></Icon>
