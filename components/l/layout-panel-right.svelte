<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9g5xl3gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j9g5xl3gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:layout-panel-right" {...props}></Icon>
