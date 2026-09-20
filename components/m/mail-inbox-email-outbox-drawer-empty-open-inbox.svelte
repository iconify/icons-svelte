<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/y/yph-txb3i.css';
import '../../css/n/nxj4rp_wf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="y9tr6bcfx"><rect class="yph-txb3i"/><path class="nxj4rp_wf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:mail-inbox-email-outbox-drawer-empty-open-inbox" {...props}></Icon>
