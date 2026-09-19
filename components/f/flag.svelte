<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l_2fxrbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="l_2fxrbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:flag" {...props}></Icon>
