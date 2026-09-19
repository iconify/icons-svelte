<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g06rgycvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g06rgycvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:arrow-all-direction" {...props}></Icon>
