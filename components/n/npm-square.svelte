<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zfn_heb_z.css';
import '../../css/m/m65mk-ths.css';
import '../../css/q/q_s4rbbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zfn_heb_z"/><path class="m65mk-ths"/><path class="q_s4rbbpt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:npm-square" {...props}></Icon>
