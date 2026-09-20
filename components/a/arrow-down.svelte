<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re3f74b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="re3f74b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-down" {...props}></Icon>
