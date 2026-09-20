<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st72lkbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="st72lkbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-horizontal-up-stipple-up-right" {...props}></Icon>
