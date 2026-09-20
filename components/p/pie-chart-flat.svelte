<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i5780hbgv.css';
import '../../css/a/anm302bgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="i5780hbgv"/><path class="anm302bgc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:pie-chart-flat" {...props}></Icon>
