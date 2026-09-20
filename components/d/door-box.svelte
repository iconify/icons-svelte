<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4oiey3br.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="z4oiey3br"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:door-box" {...props}></Icon>
