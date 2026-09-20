<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m06b_wb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":63,"height":64};
const content = `<path class="m06b_wb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-information-us" {...props}></Icon>
