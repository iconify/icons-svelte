<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyd_hm.css';
import '../../css/y/ydovum.css';
import '../../css/z/zokflo.css';
import '../../css/x/xgpo5m.css';
import '../../css/s/so-from-56.css';
import '../../css/f/fill-to-1.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xyd_hm ydovum"/><path class="ydovum zokflo"/><path class="xgpo5m ydovum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:moon-filled" {...props}></Icon>
