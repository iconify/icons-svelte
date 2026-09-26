<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i3eru1kha.css';
import '../../css/r/r59hdg7vl.css';
import '../../css/c/c73t34bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i3eru1kha"/><path class="r59hdg7vl"/><path class="c73t34bfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:file-image-bold" {...props}></Icon>
