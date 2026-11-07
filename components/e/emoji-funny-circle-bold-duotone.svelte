<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnb90nbxf.css';
import '../../css/n/nqs92bb2p.css';
import '../../css/i/ijcx_p_-b.css';
import '../../css/o/o7_qo9bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnb90nbxf"/><path class="nqs92bb2p"/><path class="ijcx_p_-b"/><path class="o7_qo9bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:emoji-funny-circle-bold-duotone" {...props}></Icon>
