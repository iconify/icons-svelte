<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wl1-0k6eb.css';
import '../../css/j/jj9_iwbid.css';
import '../../css/s/s9gd7lbys.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wl1-0k6eb"/><path class="jj9_iwbid"/><path class="s9gd7lbys"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:glowstone" {...props}></Icon>
