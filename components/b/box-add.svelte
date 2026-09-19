<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/usj20usnf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="usj20usnf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:box-add" {...props}></Icon>
