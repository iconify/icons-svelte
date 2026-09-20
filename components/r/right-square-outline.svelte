<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4d07tkli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k4d07tkli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:right-square-outline" {...props}></Icon>
