<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mg77dbcxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mg77dbcxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:list-select" {...props}></Icon>
