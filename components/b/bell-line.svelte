<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-prufbkf.css';
import '../../css/g/gsx2n78yf.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 j-prufbkf"/><path class="clr-i-outline clr-i-outline-path-2 gsx2n78yf"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:bell-line" {...props}></Icon>
