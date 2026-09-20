<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chrsyeb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="chrsyeb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-powerpoint-2013-dark" {...props}></Icon>
