<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/ix1g3dbsk.css';
import '../../css/n/nauxe-bnh.css';
import '../../css/r/rer6grbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ix1g3dbsk"/><path clip-rule="evenodd" class="nauxe-bnh"/><path class="rer6grbox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:pill-jar2-filled" {...props}></Icon>
