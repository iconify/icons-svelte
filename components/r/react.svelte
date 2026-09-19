<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f5zt_gved.css';
import '../../css/z/z-s_b7rqn.css';
import '../../css/n/na80c_qqt.css';
import '../../css/h/hf8_b9b8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f5zt_gved"/><path class="z-s_b7rqn"/><path class="na80c_qqt"/><path class="hf8_b9b8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:react" {...props}></Icon>
