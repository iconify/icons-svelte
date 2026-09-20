<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gx1qguu2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gx1qguu2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ellipsis-dots-h" {...props}></Icon>
