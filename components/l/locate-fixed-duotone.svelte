<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iidnv_bgd.css';
import '../../css/f/f29fwjbso.css';
import '../../css/s/s0a2qk_lk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iidnv_bgd"/><path class="f29fwjbso"/><path clip-rule="evenodd" class="s0a2qk_lk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:locate-fixed-duotone" {...props}></Icon>
