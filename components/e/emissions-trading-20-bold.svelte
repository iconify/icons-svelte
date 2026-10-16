<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2arlh74i.css';
import '../../css/g/gfbgo5b2g.css';
import '../../css/o/owlyunb_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k2arlh74i"/><path class="gfbgo5b2g"/><path class="owlyunb_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:emissions-trading-20-bold" {...props}></Icon>
