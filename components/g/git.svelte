<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxafrrtfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mxafrrtfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:git" {...props}></Icon>
