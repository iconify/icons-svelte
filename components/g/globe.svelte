<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hmiy7m5fl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hmiy7m5fl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:globe" {...props}></Icon>
