<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-t2sub4u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="z-t2sub4u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-brain-1" {...props}></Icon>
