<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhbyxpbbq.css';
import '../../css/q/qxnbbh5_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zhbyxpbbq"/><path class="qxnbbh5_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:erugo-light" {...props}></Icon>
