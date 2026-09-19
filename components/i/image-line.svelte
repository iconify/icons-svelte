<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upelnybhu.css';
import '../../css/g/g98mmptrb.css';
import '../../css/c/c59m8zuqm.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 upelnybhu"/><path class="clr-i-outline clr-i-outline-path-2 g98mmptrb"/><path class="c59m8zuqm clr-i-outline clr-i-outline-path-3"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:image-line" {...props}></Icon>
