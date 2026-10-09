<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nk0e34b5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nk0e34b5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:green-steel-20-bold" {...props}></Icon>
