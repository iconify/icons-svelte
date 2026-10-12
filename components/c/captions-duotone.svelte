<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gr5g80bwz.css';
import '../../css/m/mftdyfxbo.css';
import '../../css/n/nn4w9sb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="gr5g80bwz"/><path class="mftdyfxbo"/><path class="nn4w9sb3d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:captions-duotone" {...props}></Icon>
