<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bse-cb6-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<rect class="bse-cb6-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:interface-geometric-square-square-geometric-design-shape-shapes" {...props}></Icon>
