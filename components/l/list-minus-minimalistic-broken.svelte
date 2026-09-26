<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f8edcu39k.css';
import '../../css/c/cvwfe6bhh.css';
import '../../css/q/q77q3mvdo.css';
import '../../css/g/glpogpcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f8edcu39k"/><path class="cvwfe6bhh"/><path class="q77q3mvdo"/><path class="glpogpcqk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-minus-minimalistic-broken" {...props}></Icon>
