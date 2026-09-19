<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ri9ji-5tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ri9ji-5tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:diploma-1" {...props}></Icon>
