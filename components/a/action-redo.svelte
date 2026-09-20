<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oevl6j0cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="oevl6j0cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:action-redo" {...props}></Icon>
