<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fa6ra5b2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="fa6ra5b2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:apps" {...props}></Icon>
