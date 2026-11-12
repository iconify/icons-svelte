<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lu8n2uq5t.css';
import '../../css/r/r8rvkkb1c.css';
import '../../css/n/n48ro9d0t.css';
import '../../css/b/b4kxn7twd.css';
import '../../css/p/prdcoipkx.css';
import '../../css/g/gsn16rx_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lu8n2uq5t"/><path class="r8rvkkb1c"/><path class="n48ro9d0t"/><path class="b4kxn7twd"/><path class="prdcoipkx"/><path class="gsn16rx_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rackpad-light" {...props}></Icon>
