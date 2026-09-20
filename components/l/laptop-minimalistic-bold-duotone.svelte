<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vo2zbvecc.css';
import '../../css/z/z49wz6bue.css';
import '../../css/c/ce6ok6s3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vo2zbvecc"/><path class="z49wz6bue"/><path class="ce6ok6s3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:laptop-minimalistic-bold-duotone" {...props}></Icon>
