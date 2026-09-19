<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/y/ym9ihsbta.css';
import '../../css/v/v59288b0k.css';
import '../../css/p/pjlpop4pn.css';
import '../../css/k/k1ou4_b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="ym9ihsbta"/><path class="v59288b0k"/><path class="pjlpop4pn"/><path class="k1ou4_b5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:map-pinpoint-01" {...props}></Icon>
