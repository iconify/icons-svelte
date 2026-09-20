<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo_l9zrur.css';
import '../../css/i/ij2x_72vy.css';
import '../../css/m/mjqsc3bcv.css';
import '../../css/a/as1-0ybuo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="yo_l9zrur"/><g class="ij2x_72vy"><path class="mjqsc3bcv"/><circle class="as1-0ybuo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:add-button" {...props}></Icon>
