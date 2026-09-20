<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o2s99bc2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="o2s99bc2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-w" {...props}></Icon>
