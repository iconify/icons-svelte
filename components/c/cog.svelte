<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/k5l_zwbaq.css';
import '../../css/m/myrub2tat.css';
import '../../css/q/qvg2egx2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="k5l_zwbaq"/><path class="myrub2tat"/><path class="qvg2egx2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:cog" {...props}></Icon>
