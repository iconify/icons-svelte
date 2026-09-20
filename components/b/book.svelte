<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3-yu6bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="u3-yu6bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:book" {...props}></Icon>
