<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tf3_fw_kp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tf3_fw_kp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:3d-curve-auto-colon" {...props}></Icon>
