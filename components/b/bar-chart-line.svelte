<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omuhb1bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="omuhb1bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bar-chart-line" {...props}></Icon>
