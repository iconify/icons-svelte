<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d1x_6zbkv.css';
import '../../css/t/ty0x_qewu.css';
import '../../css/a/aqt2kdbol.css';
import '../../css/w/w36ns7bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="d1x_6zbkv"/><path class="ty0x_qewu"/><path class="aqt2kdbol"/><path class="w36ns7bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:lesotho" {...props}></Icon>
