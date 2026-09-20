<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wug2whbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="wug2whbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:nature-ecology-clover-plant-leaf-tree-flower-luck-lucky" {...props}></Icon>
