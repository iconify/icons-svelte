<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k0mu8gnlh.css';
import '../../css/i/i9mwivbls.css';
import '../../css/h/hcghnfbeu.css';
import '../../css/q/q1k9b48ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="k0mu8gnlh"/><path class="i9mwivbls"/><path class="hcghnfbeu"/><path class="q1k9b48ek"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:mouse-circle-bold" {...props}></Icon>
