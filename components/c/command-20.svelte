<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mn9jvab9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mn9jvab9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:command-20" {...props}></Icon>
