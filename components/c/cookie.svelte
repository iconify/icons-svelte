<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwhpnrv1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":472};
const content = `<path class="iwhpnrv1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:cookie" {...props}></Icon>
