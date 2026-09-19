<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a6uie1dvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a6uie1dvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:chart-mixed-dollar-outline" {...props}></Icon>
