<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1stjnble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p1stjnble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightbulb-20" {...props}></Icon>
