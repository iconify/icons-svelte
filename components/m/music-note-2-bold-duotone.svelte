<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/ff-z_pbgs.css';
import '../../css/u/ugz6q-brk.css';
import '../../css/e/eg30hg2ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ff-z_pbgs"/><path class="ugz6q-brk"/><path class="eg30hg2ty"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:music-note-2-bold-duotone" {...props}></Icon>
