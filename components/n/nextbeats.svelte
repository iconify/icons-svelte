<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_49x_b_v.css';
import '../../css/w/wr-7e-6db.css';
import '../../css/w/wyeldhbnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m_49x_b_v"/><path class="wr-7e-6db"/><path class="wyeldhbnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextbeats" {...props}></Icon>
