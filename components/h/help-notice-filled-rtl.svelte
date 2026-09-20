<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auypmabvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="auypmabvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:help-notice-filled-rtl" {...props}></Icon>
