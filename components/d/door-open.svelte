<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7a0dzb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="a7a0dzb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:door-open" {...props}></Icon>
