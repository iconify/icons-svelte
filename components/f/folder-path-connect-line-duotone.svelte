<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ifmngxb5v.css';
import '../../css/c/c8yirybsn.css';
import '../../css/h/hkd5jdb0n.css';
import '../../css/d/ds1vr8vmh.css';
import '../../css/s/swsab_86e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ifmngxb5v"/><path class="c8yirybsn"/><path class="hkd5jdb0n"/><path class="ds1vr8vmh"/><circle class="swsab_86e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-path-connect-line-duotone" {...props}></Icon>
