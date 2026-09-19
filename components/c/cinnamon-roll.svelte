<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/pxy5wxb2o.css';
import '../../css/h/h2tkw0b0p.css';
import '../../css/k/kqlaetbyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="pxy5wxb2o"/><path class="h2tkw0b0p"/><path class="kqlaetbyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cinnamon-roll" {...props}></Icon>
