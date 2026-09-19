<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fjv3yr_cl.css';
import '../../css/e/e_m9s3bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="cuyn6tgcc"><path class="fjv3yr_cl"/><path clip-rule="evenodd" class="e_m9s3bio"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:masked2x-outline" {...props}></Icon>
