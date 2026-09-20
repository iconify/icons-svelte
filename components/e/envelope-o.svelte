<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr4f3tbci.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vr4f3tbci"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:envelope-o" {...props}></Icon>
