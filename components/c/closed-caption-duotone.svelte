<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/txva6ic1h.css';
import '../../css/m/mgl97wcfv.css';
import '../../css/s/s805e4aqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="txva6ic1h"/><path class="mgl97wcfv"/><path class="s805e4aqh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:closed-caption-duotone" {...props}></Icon>
