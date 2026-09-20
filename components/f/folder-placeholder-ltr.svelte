<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmm6urb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rmm6urb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:folder-placeholder-ltr" {...props}></Icon>
