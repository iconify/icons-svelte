<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnu9g8bun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="dnu9g8bun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-up-right-stipple-inner" {...props}></Icon>
