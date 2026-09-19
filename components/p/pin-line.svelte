<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i6nl4-bla.css';
import '../../css/c/ch4baybtb.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 i6nl4-bla"/><path class="ch4baybtb clr-i-outline clr-i-outline-path-2"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:pin-line" {...props}></Icon>
