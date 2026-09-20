<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbssek_nw.css';
import '../../css/p/pv56n73nc.css';
import '../../css/a/a47dmxbwp.css';
import '../../css/p/pkcocdbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vbssek_nw"/><path class="pv56n73nc"/><path class="a47dmxbwp"/><path class="pkcocdbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:posthog" {...props}></Icon>
