<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e727a1bty.css';
import '../../css/r/r98qut7eh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="e727a1bty"/><path class="r98qut7eh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:padding-top" {...props}></Icon>
