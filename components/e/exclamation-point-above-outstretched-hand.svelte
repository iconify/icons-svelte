<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cccwf_yei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cccwf_yei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:exclamation-point-above-outstretched-hand" {...props}></Icon>
