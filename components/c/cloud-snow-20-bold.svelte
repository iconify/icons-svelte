<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fk51r8bob.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fk51r8bob"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-snow-20-bold" {...props}></Icon>
