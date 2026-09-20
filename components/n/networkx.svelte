<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1g1p6r1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="w1g1p6r1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:networkx" {...props}></Icon>
