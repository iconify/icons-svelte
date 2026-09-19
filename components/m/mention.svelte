<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e656cy2pz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e656cy2pz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mention" {...props}></Icon>
