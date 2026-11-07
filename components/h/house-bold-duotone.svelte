<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-ste9rjs.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/b/bp5vlbc9d.css';
import '../../css/g/gam1sgbnn.css';
import '../../css/x/x047q_bxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z-ste9rjs"/><g class="xtpeb-edw"><path class="bp5vlbc9d"/><path class="gam1sgbnn"/><path class="x047q_bxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:house-bold-duotone" {...props}></Icon>
