<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xo6egfo-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xo6egfo-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ellipsis-circle" {...props}></Icon>
