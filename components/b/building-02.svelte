<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/jl7qy2b6n.css';
import '../../css/y/y31lx-nom.css';
import '../../css/f/frhepll3l.css';
import '../../css/m/m07rxpscr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="jl7qy2b6n"/><path class="y31lx-nom"/><path class="frhepll3l"/><path class="m07rxpscr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:building-02" {...props}></Icon>
