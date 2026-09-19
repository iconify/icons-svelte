<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pzxv190ut.css';
import '../../css/x/xuz284bnw.css';
import '../../css/r/rysm2pqae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pzxv190ut"/><circle class="xuz284bnw"/><path class="rysm2pqae"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:id-verified" {...props}></Icon>
