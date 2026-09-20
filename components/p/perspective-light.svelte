<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f0orljh9w.css';
import '../../css/v/v5_kwmb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<g class="ft5dv1b6b"><path class="f0orljh9w"/><path clip-rule="evenodd" class="v5_kwmb_i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:perspective-light" {...props}></Icon>
