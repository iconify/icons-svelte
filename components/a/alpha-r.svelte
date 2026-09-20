<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdk8ibl3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="qdk8ibl3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-r" {...props}></Icon>
