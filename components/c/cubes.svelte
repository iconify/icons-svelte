<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uh-v3mdgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2176,"height":1792};
const content = `<path class="uh-v3mdgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:cubes" {...props}></Icon>
