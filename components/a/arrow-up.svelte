<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cvead4brz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":16};
const content = `<path class="cvead4brz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:arrow-up" {...props}></Icon>
