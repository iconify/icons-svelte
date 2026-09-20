<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xgxs8rbcn.css';
import '../../css/t/t2982abjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="xgxs8rbcn"/><path class="t2982abjv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:pin-alt-2-duotone" {...props}></Icon>
