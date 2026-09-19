<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oq1j-2omy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oq1j-2omy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:fish2-happy" {...props}></Icon>
