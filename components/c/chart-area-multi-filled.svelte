<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrbyzachg.css';
import '../../css/p/p5hooobjg.css';
import '../../css/l/lz3_q5bvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrbyzachg"/><path class="p5hooobjg"/><path class="lz3_q5bvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-area-multi-filled" {...props}></Icon>
