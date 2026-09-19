<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvlen3c-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kvlen3c-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:buromobelexperte" {...props}></Icon>
