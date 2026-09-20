<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk0-2pbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yk0-2pbjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:header" {...props}></Icon>
