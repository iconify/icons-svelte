<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tynb5sbsm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tynb5sbsm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:number-stroke-16" {...props}></Icon>
