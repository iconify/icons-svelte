<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5z-yx4il.css';
import '../../css/w/wm3j448rr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5z-yx4il"/><path class="wm3j448rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-add-bold" {...props}></Icon>
