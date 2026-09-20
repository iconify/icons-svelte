<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gja2twb9p.css';
import '../../css/q/qwc-lyped.css';
import '../../css/s/s42la0b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle clip-rule="evenodd" transform="rotate(-13.286 255.94 255.868)" class="gja2twb9p"/><path clip-rule="evenodd" class="qwc-lyped"/><path clip-rule="evenodd" class="s42la0b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-light" {...props}></Icon>
