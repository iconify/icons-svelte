<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2sxbmu3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="e2sxbmu3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:display-alt" {...props}></Icon>
