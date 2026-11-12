<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmi7xr5ec.css';
import '../../css/r/re6u8gbgx.css';
import '../../css/b/bpn6pm9pz.css';
import '../../css/u/uacs7ebvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmi7xr5ec"/><path class="re6u8gbgx"/><path class="bpn6pm9pz"/><path class="uacs7ebvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidbrainz-dark" {...props}></Icon>
