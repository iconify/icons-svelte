<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jonzy7b1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jonzy7b1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:bank" {...props}></Icon>
