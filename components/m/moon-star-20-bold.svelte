<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohg506bqr.css';
import '../../css/y/yttl06bmd.css';
import '../../css/e/e-yptyqrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ohg506bqr"/><path class="yttl06bmd"/><path class="e-yptyqrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:moon-star-20-bold" {...props}></Icon>
