<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn4sofbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hn4sofbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:filter-remove-16" {...props}></Icon>
