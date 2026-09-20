<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nntdrfmki.css';
import '../../css/r/ra3icybqn.css';
import '../../css/i/ia-wcjbpv.css';
import '../../css/s/shxjsdxjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nntdrfmki"/><path class="ra3icybqn"/><path clip-rule="evenodd" class="ia-wcjbpv"/><path class="shxjsdxjs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clapperboard-text-bold" {...props}></Icon>
