<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/t/tbli70boo.css';
import '../../css/h/hhkbedc5d.css';
import '../../css/v/vnor8oomw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="tbli70boo"/><path class="hhkbedc5d"/><path class="vnor8oomw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:asteroid-bold" {...props}></Icon>
