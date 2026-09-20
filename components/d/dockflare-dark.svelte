<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyeglmmtr.css';
import '../../css/a/akc_yvbhb.css';
import '../../css/u/ua_s72b4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eyeglmmtr"/><path class="akc_yvbhb"/><path class="ua_s72b4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockflare-dark" {...props}></Icon>
