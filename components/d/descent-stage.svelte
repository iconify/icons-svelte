<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwo-zkbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mwo-zkbxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:descent-stage" {...props}></Icon>
