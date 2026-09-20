<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqq126x0h.css';
import '../../css/v/vzdg82byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="aqq126x0h"/><path class="vzdg82byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:gloves" {...props}></Icon>
