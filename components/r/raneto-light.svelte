<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tr1vn-rwh.css';
import '../../css/v/v904cs9gt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tr1vn-rwh"/><path class="v904cs9gt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:raneto-light" {...props}></Icon>
