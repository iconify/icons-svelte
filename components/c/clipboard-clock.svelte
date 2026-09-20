<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/b/baqd6ablr.css';
import '../../css/z/zs13s_bpz.css';
import '../../css/u/u8u9_5smu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="baqd6ablr"/><circle class="zs13s_bpz"/><rect class="u8u9_5smu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:clipboard-clock" {...props}></Icon>
