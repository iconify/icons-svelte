<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e14i29iin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e14i29iin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:cloud-snow" {...props}></Icon>
