<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn8bvackf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="pn8bvackf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chevron-left-circle" {...props}></Icon>
