<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/c/c6n_3bcym.css';
import '../../css/f/ff69knbjn.css';
import '../../css/s/sp1othbmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="c6n_3bcym"/><path class="ff69knbjn"/><path class="sp1othbmo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:game-controller-03" {...props}></Icon>
