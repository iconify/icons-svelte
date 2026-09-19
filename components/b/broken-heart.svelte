<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x_1c0ebea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="x_1c0ebea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:broken-heart" {...props}></Icon>
