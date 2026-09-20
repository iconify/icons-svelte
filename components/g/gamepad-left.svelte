<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h5zr88b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="h5zr88b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:gamepad-left" {...props}></Icon>
