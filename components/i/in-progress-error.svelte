<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c55vgcbjc.css';
import '../../css/n/n-obmabwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c55vgcbjc"/><path class="n-obmabwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:in-progress-error" {...props}></Icon>
