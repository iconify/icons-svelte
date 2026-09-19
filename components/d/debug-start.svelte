<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/voyl-4j-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="voyl-4j-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-start" {...props}></Icon>
