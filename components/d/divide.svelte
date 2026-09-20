<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqqwh7w1i.css';
import '../../css/z/zg9vbp76i.css';
import '../../css/m/m87cjre2p.css';
import '../../css/m/mc5erxb5b.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/j/jl290tb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="sqqwh7w1i"><path class="zg9vbp76i"/><circle class="m87cjre2p"/><circle class="mc5erxb5b"/></g><g class="ij2x_72vy"><path class="jl290tb9n"/><circle class="m87cjre2p"/><circle class="mc5erxb5b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:divide" {...props}></Icon>
