<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu8aw7boy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qu8aw7boy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pie-chart-alt-outline" {...props}></Icon>
