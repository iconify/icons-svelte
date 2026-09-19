<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o51njj7bl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o51njj7bl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:edit-undo-stroke-16" {...props}></Icon>
