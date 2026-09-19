<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/q926-gbel.css';
import '../../css/s/s_bdsyxad.css';
import '../../css/i/iqbnmdmbt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="q926-gbel"/><path class="s_bdsyxad"/><path class="iqbnmdmbt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:panda" {...props}></Icon>
