<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js0ml5b3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="js0ml5b3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:peace" {...props}></Icon>
