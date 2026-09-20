<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcqhywbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gcqhywbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:align-center-horizontal-2-16" {...props}></Icon>
