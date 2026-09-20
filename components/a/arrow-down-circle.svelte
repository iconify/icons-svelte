<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxfg_hu8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="uxfg_hu8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down-circle" {...props}></Icon>
