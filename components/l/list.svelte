<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1bwmrgjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d1bwmrgjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:list" {...props}></Icon>
