<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzqfxbb-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="tzqfxbb-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-outer-light-left-stipple" {...props}></Icon>
