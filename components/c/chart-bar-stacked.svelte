<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/c/cldzy6oen.css';
import '../../css/y/y0rn8rb3v.css';
import '../../css/e/ej6bo1bfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cldzy6oen"/><rect class="y0rn8rb3v"/><rect class="ej6bo1bfx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:chart-bar-stacked" {...props}></Icon>
