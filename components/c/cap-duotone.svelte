<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/ft4bv5pda.css';
import '../../css/m/mepxv4b3w.css';
import '../../css/o/os72iwz3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ft4bv5pda"/><path class="mepxv4b3w"/><path class="os72iwz3x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cap-duotone" {...props}></Icon>
