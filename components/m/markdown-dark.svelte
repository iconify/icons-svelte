<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff__zcblq.css';
import '../../css/q/qsplvob1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":208,"height":128};
const content = `<path class="ff__zcblq"/><path class="qsplvob1b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:markdown-dark" {...props}></Icon>
