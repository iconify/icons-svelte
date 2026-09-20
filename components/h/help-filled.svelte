<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/t25zbvb4l.css';
import '../../css/y/ytlnqnvjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="t25zbvb4l"/><path vector-effect="non-scaling-stroke" class="ytlnqnvjr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:help-filled" {...props}></Icon>
