<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5-fw6cio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="e5-fw6cio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:chest" {...props}></Icon>
