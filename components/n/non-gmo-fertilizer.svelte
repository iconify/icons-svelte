<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0nb7cc6b.css';
import '../../css/o/o3ain3blr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d0nb7cc6b"/><path class="o3ain3blr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:non-gmo-fertilizer" {...props}></Icon>
