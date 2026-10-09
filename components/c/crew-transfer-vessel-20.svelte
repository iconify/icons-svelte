<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lhg7ko28s.css';
import '../../css/y/ywq58thzo.css';
import '../../css/o/oh1_vxmzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lhg7ko28s"/><path class="ywq58thzo"/><path class="oh1_vxmzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:crew-transfer-vessel-20" {...props}></Icon>
