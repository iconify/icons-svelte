<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lvoecyb6c.css';
import '../../css/m/mhxymalnj.css';
import '../../css/t/teg2gbcuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lvoecyb6c"/><path class="mhxymalnj"/><path class="teg2gbcuk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:masks-duotone" {...props}></Icon>
