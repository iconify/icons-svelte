<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb0tbwbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yb0tbwbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:creative-commons-by-fill" {...props}></Icon>
