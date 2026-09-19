<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ck0molb8m.css';
import '../../css/m/m2o3sh-9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="ck0molb8m clr-i-solid clr-i-solid-path-1"/><path class="m2o3sh-9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:battery-solid" {...props}></Icon>
