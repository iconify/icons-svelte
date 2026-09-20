<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/g/g0wdbbh0b.css';
import '../../css/i/i3pcmrmmi.css';
import '../../css/k/k3wcmpbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="g0wdbbh0b"/><path class="i3pcmrmmi"/><path clip-rule="evenodd" class="k3wcmpbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:radio-sharp-duotone" {...props}></Icon>
