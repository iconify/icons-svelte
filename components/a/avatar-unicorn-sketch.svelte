<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kda6is2bg.css';
import '../../css/x/xcl4by4_y.css';
import '../../css/s/s1pwchbtz.css';
import '../../css/c/c_pueebqi.css';
import '../../css/c/cpx80hnid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kda6is2bg"/><path class="wm-k xcl4by4_y"/><path class="s1pwchbtz wm-a"/><path class="c_pueebqi wm-k"/><path class="cpx80hnid wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:avatar-unicorn-sketch" {...props}></Icon>
