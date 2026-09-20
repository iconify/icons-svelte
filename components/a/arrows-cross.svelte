<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuikkvv7i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xuikkvv7i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:arrows-cross" {...props}></Icon>
