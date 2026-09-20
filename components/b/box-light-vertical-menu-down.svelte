<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/es3w6ybnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="es3w6ybnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-vertical-menu-down" {...props}></Icon>
