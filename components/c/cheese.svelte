<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g8pbt_7ho.css';
import '../../css/k/k6hr5pbmw.css';
import '../../css/r/r757d9zet.css';
import '../../css/u/uslbr7byg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="g8pbt_7ho"/><path class="k6hr5pbmw"/><path class="r757d9zet"/><path class="uslbr7byg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:cheese" {...props}></Icon>
