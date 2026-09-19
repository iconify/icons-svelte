<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t18islbco.css';
import '../../css/m/mz8pfhblh.css';
import '../../css/d/dnpvs6bkb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t18islbco"/><path class="mz8pfhblh"/><path class="dnpvs6bkb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-block-01" {...props}></Icon>
