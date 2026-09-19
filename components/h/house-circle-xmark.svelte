<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e75fnac6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="e75fnac6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-circle-xmark" {...props}></Icon>
