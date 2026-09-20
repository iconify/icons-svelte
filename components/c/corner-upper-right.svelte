<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuhw34bft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fuhw34bft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:corner-upper-right" {...props}></Icon>
