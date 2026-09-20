<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v17nmnbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v17nmnbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:laptop" {...props}></Icon>
