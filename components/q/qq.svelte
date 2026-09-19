<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n24_ilbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n24_ilbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:qq" {...props}></Icon>
