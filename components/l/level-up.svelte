<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fja0ejbdp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fja0ejbdp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:level-up" {...props}></Icon>
