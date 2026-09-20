<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfpj2xyvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mfpj2xyvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:arrow-circle-up-solid" {...props}></Icon>
