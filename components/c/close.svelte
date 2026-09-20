<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oi44tcbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oi44tcbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:close" {...props}></Icon>
