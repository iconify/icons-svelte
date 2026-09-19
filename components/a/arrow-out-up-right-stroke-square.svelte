<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4ycw1bvi.css';
import '../../css/r/r-n6f1bae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4ycw1bvi"/><path class="r-n6f1bae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-out-up-right-stroke-square" {...props}></Icon>
