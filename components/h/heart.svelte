<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ug8z3acqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ug8z3acqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:heart" {...props}></Icon>
