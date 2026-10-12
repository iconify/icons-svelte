<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lh5-28bek.css';
import '../../css/b/bt9-2rbpz.css';
import '../../css/p/pi2xzdbqy.css';
import '../../css/o/ohm10wuwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lh5-28bek"/><circle transform="rotate(90 12 12)" class="bt9-2rbpz"/><rect class="pi2xzdbqy"/><path class="ohm10wuwo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="andrsrxn:lock-circle" {...props}></Icon>
