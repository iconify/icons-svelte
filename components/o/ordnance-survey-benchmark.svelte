<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj17dhbez.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pj17dhbez"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ordnance-survey-benchmark" {...props}></Icon>
