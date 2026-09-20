<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvv6vdecf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pvv6vdecf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:plus-circle" {...props}></Icon>
