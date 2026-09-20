<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmw2_n2yc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fmw2_n2yc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:japan-police-station" {...props}></Icon>
