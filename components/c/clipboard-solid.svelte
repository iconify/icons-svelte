<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/emikoz2ew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="emikoz2ew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:clipboard-solid" {...props}></Icon>
