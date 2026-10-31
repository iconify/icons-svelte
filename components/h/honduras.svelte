<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv__ntbgi.css';
import '../../css/d/d1x_6zbkv.css';
import '../../css/m/m3x6dbb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="hv__ntbgi"/><path class="d1x_6zbkv"/><path class="m3x6dbb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:honduras" {...props}></Icon>
