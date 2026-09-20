<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd0piybon.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bd0piybon"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-down" {...props}></Icon>
