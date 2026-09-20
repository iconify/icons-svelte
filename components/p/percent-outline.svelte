<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq8y7_swj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hq8y7_swj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:percent-outline" {...props}></Icon>
