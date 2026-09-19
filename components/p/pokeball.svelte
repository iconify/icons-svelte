<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zeggah3kn.css';
import '../../css/p/pfa780btb.css';
import '../../css/v/vvwsy1zbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="zeggah3kn"/><path class="pfa780btb"/><path class="vvwsy1zbp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pokeball" {...props}></Icon>
