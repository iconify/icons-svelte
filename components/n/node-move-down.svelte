<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/n/nf8asibfv.css';
import '../../css/v/v_u7lbc8p.css';
import '../../css/i/iqbu_qwxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="nf8asibfv"/><path class="v_u7lbc8p"/><path class="iqbu_qwxd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:node-move-down" {...props}></Icon>
