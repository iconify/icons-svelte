<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erzf03bmv.css';
import '../../css/k/kd8y0_bxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="erzf03bmv"/><path class="kd8y0_bxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:gl-1x1" {...props}></Icon>
