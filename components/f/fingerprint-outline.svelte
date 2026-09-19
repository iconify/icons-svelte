<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/t/tx-2acchp.css';
import '../../css/l/l-ehgjbqb.css';
import '../../css/e/ei8zogbbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="tx-2acchp"/><path class="l-ehgjbqb"/><path class="ei8zogbbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:fingerprint-outline" {...props}></Icon>
