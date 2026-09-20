<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eam5p6x4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="eam5p6x4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-a-fill" {...props}></Icon>
