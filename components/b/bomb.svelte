<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/g03ovcved.css';
import '../../css/m/m1g9nibzc.css';
import '../../css/a/awab4gbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="g03ovcved"/><path class="m1g9nibzc"/><path class="awab4gbil"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:bomb" {...props}></Icon>
