<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clcsdocbl.css';
import '../../css/a/a519wcbzu.css';
import '../../css/n/nbedlgb6f.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="clcsdocbl clr-i-solid clr-i-solid-path-1"/><path class="a519wcbzu clr-i-solid clr-i-solid-path-2"/><path class="clr-i-solid clr-i-solid-path-3 nbedlgb6f"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:alarm-clock-solid" {...props}></Icon>
