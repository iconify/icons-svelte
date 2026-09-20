<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r0zr1abhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r0zr1abhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:rotate-left" {...props}></Icon>
