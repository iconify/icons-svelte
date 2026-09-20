<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gapqp1bwb.css';
import '../../css/h/hs8q6tbjn.css';
import '../../css/d/dcxz7vgia.css';
import '../../css/v/vheqg2b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="gapqp1bwb"/><path class="hs8q6tbjn"/><path clip-rule="evenodd" class="dcxz7vgia"/><path clip-rule="evenodd" class="vheqg2b0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:airbuds-check-bold" {...props}></Icon>
