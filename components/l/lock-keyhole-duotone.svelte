<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qmm42bchc.css';
import '../../css/w/w-olv5bzw.css';
import '../../css/e/esf9wtdqe.css';
import '../../css/p/pw6-rqbfc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qmm42bchc"/><path class="w-olv5bzw"/><path class="esf9wtdqe"/><path class="pw6-rqbfc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lock-keyhole-duotone" {...props}></Icon>
