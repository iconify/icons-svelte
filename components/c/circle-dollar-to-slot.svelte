<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ny9xkfbzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ny9xkfbzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:circle-dollar-to-slot" {...props}></Icon>
