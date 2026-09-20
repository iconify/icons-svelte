<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ij2x_72vy.css';
import '../../css/v/vhi7r2jzj.css';
import '../../css/l/lifeqcx7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="ij2x_72vy"><path class="vhi7r2jzj"/><path class="lifeqcx7d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:fast-forward-button" {...props}></Icon>
