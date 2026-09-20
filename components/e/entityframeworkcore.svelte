<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vifyjob0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="vifyjob0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:entityframeworkcore" {...props}></Icon>
