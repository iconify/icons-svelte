<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzd3z6cbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tzd3z6cbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:arrow-big-left-20-bold" {...props}></Icon>
