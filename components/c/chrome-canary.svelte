<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd6mj9e-i.css';
import '../../css/d/dn5b1_f-b.css';
import '../../css/p/phprfuhss.css';
import '../../css/p/p6_7y-bmy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vd6mj9e-i"/><circle class="dn5b1_f-b"/><path class="phprfuhss"/><path class="p6_7y-bmy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:chrome-canary" {...props}></Icon>
