<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/i_dcv8bbe.css';
import '../../css/r/rf9tq_bna.css';
import '../../css/i/i29n7n-0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="i_dcv8bbe"/><path class="rf9tq_bna"/><path class="i29n7n-0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:atom" {...props}></Icon>
