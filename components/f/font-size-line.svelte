<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucjk8rbpt.css';
import '../../css/u/uss_0hflh.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 ucjk8rbpt"/><path class="clr-i-outline clr-i-outline-path-2 uss_0hflh"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:font-size-line" {...props}></Icon>
