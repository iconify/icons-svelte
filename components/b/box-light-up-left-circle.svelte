<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru2_96wgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ru2_96wgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-up-left-circle" {...props}></Icon>
