<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/a/ayl3yr5fw.css';
import '../../css/w/wyu8pxfbe.css';
import '../../css/a/apm0xsbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ayl3yr5fw"/><path class="wyu8pxfbe"/><path clip-rule="evenodd" class="apm0xsbgl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:folder-path-connect-bold-duotone" {...props}></Icon>
