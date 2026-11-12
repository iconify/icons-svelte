<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyp46zrds.css';
import '../../css/s/s4z2tns2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zyp46zrds"/><path class="s4z2tns2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-messages-light" {...props}></Icon>
