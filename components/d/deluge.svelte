<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dif6p1bms.css';
import '../../css/u/u1-7rbomv.css';
import '../../css/s/smgw8kb-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dif6p1bms"/><path class="u1-7rbomv"/><path class="smgw8kb-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:deluge" {...props}></Icon>
