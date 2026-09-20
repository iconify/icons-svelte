<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx06-ybtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yx06-ybtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:corner-lower-right" {...props}></Icon>
