<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/a/az0dxebks.css';
import '../../css/n/nxcr2vf7w.css';
import '../../css/f/frl_qifow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><circle class="az0dxebks"/><path class="nxcr2vf7w"/><path class="frl_qifow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:neutral-face-light" {...props}></Icon>
