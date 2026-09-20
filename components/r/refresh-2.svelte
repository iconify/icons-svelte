<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/lybqr_27c.css';
import '../../css/b/btz76nbfi.css';
import '../../css/z/zurft_ftu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lybqr_27c"/><path class="btz76nbfi"/><path class="zurft_ftu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:refresh-2" {...props}></Icon>
