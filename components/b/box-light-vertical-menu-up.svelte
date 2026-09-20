<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4p19wb-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="k4p19wb-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-menu-up" {...props}></Icon>
