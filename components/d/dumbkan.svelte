<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_pu1d1nt.css';
import '../../css/x/xifkqvb3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="e_pu1d1nt"/><path class="xifkqvb3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dumbkan" {...props}></Icon>
