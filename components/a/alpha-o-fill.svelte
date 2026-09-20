<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/op4vh8z_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="op4vh8z_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-o-fill" {...props}></Icon>
