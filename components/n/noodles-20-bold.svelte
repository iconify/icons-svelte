<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c03uu6r0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c03uu6r0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:noodles-20-bold" {...props}></Icon>
