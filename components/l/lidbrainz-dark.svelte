<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmi7xr5ec.css';
import '../../css/r/r63xavbvd.css';
import '../../css/b/bpn6pm9pz.css';
import '../../css/h/h1ql855rm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mmi7xr5ec"/><path class="r63xavbvd"/><path class="bpn6pm9pz"/><path class="h1ql855rm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:lidbrainz-dark" {...props}></Icon>
