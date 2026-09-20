<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/maxs7mbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="maxs7mbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:capture" {...props}></Icon>
