<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jds-7weev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jds-7weev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:hexagon" {...props}></Icon>
