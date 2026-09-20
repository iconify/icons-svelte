<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fqmuc8bbw.css';
import '../../css/i/ix0rkvppz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="fqmuc8bbw"/><path clip-rule="evenodd" class="ix0rkvppz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:petri-dish-lab-equipment-flat" {...props}></Icon>
