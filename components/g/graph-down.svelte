<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nydepjiqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nydepjiqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:graph-down" {...props}></Icon>
