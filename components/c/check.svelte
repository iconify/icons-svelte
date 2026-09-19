<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zmv704bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zmv704bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:check" {...props}></Icon>
