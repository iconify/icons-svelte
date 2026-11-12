<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rc_cn3gik.css';
import '../../css/f/fd3h4yb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rc_cn3gik"/><path class="fd3h4yb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:gdms-light" {...props}></Icon>
