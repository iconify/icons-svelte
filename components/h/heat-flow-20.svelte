<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ee5vtnbjr.css';
import '../../css/h/hxpk5bbgt.css';
import '../../css/f/fo22hzbij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ee5vtnbjr"/><path class="hxpk5bbgt"/><path class="fo22hzbij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heat-flow-20" {...props}></Icon>
