<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pirn0_bio.css';
import '../../css/n/n7c4a2awt.css';
import '../../css/n/nkg6ymbnc.css';
import '../../css/d/daleh4b4i.css';
import '../../css/z/zcwku4x5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pirn0_bio"/><path class="n7c4a2awt"/><path class="nkg6ymbnc"/><path class="daleh4b4i"/><path class="zcwku4x5u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-large-bold-duotone" {...props}></Icon>
