<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iudnm730z.css';
import '../../css/l/lwo5f24pv.css';
import '../../css/l/ln0ym_was.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iudnm730z"/><path class="lwo5f24pv"/><path class="ln0ym_was"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nx-witness-light" {...props}></Icon>
