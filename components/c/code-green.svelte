<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqnggccsm.css';
import '../../css/x/x0ujg73is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqnggccsm"/><path class="x0ujg73is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteocons:code-green" {...props}></Icon>
