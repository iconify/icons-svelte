<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jea36wsph.css';
import '../../css/t/tep7rtb5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":800,"height":156,"top":316.5};
const content = `<path class="jea36wsph"/><path class="tep7rtb5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:anadolujet" {...props}></Icon>
