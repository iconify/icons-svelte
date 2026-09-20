<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhzasm3by.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fhzasm3by"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:circle-information-outline" {...props}></Icon>
