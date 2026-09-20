<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcmvy2ouf.css';
import '../../css/r/rxbeq-blz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="lcmvy2ouf"/><path class="rxbeq-blz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:networkx" {...props}></Icon>
