<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpg-ue7bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="jpg-ue7bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:cloud" {...props}></Icon>
