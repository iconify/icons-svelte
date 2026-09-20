<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c01u0fyrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c01u0fyrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:eraser" {...props}></Icon>
