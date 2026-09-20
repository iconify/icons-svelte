<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eufwep-yh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="eufwep-yh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:content-video" {...props}></Icon>
