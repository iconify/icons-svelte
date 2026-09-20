<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upt1lebwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="upt1lebwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:folder-files-outline" {...props}></Icon>
