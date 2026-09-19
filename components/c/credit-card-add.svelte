<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/g3y3mu3mp.css';
import '../../css/m/mrd0i8bef.css';
import '../../css/b/bw511z_pe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="g3y3mu3mp"/><path class="mrd0i8bef"/><path class="bw511z_pe"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:credit-card-add" {...props}></Icon>
