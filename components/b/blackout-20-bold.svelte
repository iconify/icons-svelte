<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffqw9ubly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ffqw9ubly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:blackout-20-bold" {...props}></Icon>
