<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzds0la1g.css';
import '../../css/d/d1x_6zbkv.css';
import '../../css/j/j6_dfnhpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="rzds0la1g"/><path class="d1x_6zbkv"/><path class="j6_dfnhpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:cabinda" {...props}></Icon>
