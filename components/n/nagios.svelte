<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwt1ytb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lwt1ytb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nagios" {...props}></Icon>
