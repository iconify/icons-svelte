<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/s/stv4069zv.css';
import '../../css/p/pwnohqbpo.css';
import '../../css/a/aoc0sfbxe.css';
import '../../css/g/guj4ctbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="stv4069zv"/><path class="pwnohqbpo"/><circle class="aoc0sfbxe"/><circle class="guj4ctbxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-8-square-duotone" {...props}></Icon>
