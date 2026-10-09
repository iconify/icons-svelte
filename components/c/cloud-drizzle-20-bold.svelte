<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjazr7byc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="qjazr7byc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-drizzle-20-bold" {...props}></Icon>
