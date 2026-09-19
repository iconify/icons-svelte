<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/f/fxh2tf26t.css';
import '../../css/f/fkxmg5b_v.css';
import '../../css/o/ogsqvhb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="fxh2tf26t"/><path class="fkxmg5b_v"/><path class="ogsqvhb8i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cctv-off" {...props}></Icon>
