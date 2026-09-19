<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/lhzk0on9c.css';
import '../../css/b/b544j2l2n.css';
import '../../css/l/lkva_fbsk.css';
import '../../css/i/icsnh8bsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="lhzk0on9c"/><path class="b544j2l2n"/><path class="lkva_fbsk"/><path class="icsnh8bsq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:clean" {...props}></Icon>
