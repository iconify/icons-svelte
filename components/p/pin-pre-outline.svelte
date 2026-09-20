<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k330uibgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k330uibgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:pin-pre-outline" {...props}></Icon>
