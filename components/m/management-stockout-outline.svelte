<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6_cw359x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r6_cw359x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:management-stockout-outline" {...props}></Icon>
