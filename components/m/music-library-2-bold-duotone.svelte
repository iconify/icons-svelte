<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y_rajo9ac.css';
import '../../css/y/y0p50bbsn.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/o/oqzbv9bha.css';
import '../../css/f/fxy57tbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y_rajo9ac"/><path clip-rule="evenodd" class="y0p50bbsn"/><g class="mc2zb0bvp"><path class="oqzbv9bha"/><path class="fxy57tbhk"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-library-2-bold-duotone" {...props}></Icon>
