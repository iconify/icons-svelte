<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhkwq9b2s.css';
import '../../css/h/hjfbf5arh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yhkwq9b2s"/><path class="hjfbf5arh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:antenna-20-bold" {...props}></Icon>
