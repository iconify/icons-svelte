<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/u/ucim6lbjm.css';
import '../../css/w/w98ih1blg.css';
import '../../css/d/dbz_4sb8l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ucim6lbjm"/><path class="w98ih1blg"/><path class="dbz_4sb8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:fever-24px" {...props}></Icon>
