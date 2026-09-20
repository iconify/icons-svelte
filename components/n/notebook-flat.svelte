<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/mffpo8b1l.css';
import '../../css/l/lhrsd3bjm.css';
import '../../css/u/ufg_ywe-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mffpo8b1l"/><path class="lhrsd3bjm"/><path clip-rule="evenodd" class="ufg_ywe-p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:notebook-flat" {...props}></Icon>
