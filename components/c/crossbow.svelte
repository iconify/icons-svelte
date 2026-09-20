<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_2cylg5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="j_2cylg5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:crossbow" {...props}></Icon>
