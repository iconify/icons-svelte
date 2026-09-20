<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7r--kwbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y7r--kwbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:grid-bevel" {...props}></Icon>
