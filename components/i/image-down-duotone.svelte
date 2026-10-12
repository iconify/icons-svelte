<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/iyss807dj.css';
import '../../css/r/r5vy7v9xa.css';
import '../../css/f/fe81k0bsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iyss807dj"/><path class="r5vy7v9xa"/><path class="fe81k0bsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:image-down-duotone" {...props}></Icon>
