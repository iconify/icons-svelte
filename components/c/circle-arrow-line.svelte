<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5rcylbor.css';
import '../../css/s/s6cvf7btf.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 l5rcylbor"/><path class="clr-i-outline clr-i-outline-path-2 s6cvf7btf"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:circle-arrow-line" {...props}></Icon>
