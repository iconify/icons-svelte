<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgmg2zboc.css';
import '../../css/k/kbcof-b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sgmg2zboc"/><path class="kbcof-b_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:coffer" {...props}></Icon>
