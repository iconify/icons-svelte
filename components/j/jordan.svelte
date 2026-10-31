<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1x_6zbkv.css';
import '../../css/y/y55zcjfsz.css';
import '../../css/y/yrwoiybrn.css';
import '../../css/f/fa--9cbnd.css';
import '../../css/p/pf622-vpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="y55zcjfsz"/><path class="yrwoiybrn"/><path class="fa--9cbnd"/><path class="pf622-vpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:jordan" {...props}></Icon>
