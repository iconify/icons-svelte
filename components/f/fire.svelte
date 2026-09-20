<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov04gg5zt.css';
import '../../css/j/j1t---_1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ov04gg5zt"/><path class="j1t---_1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:fire" {...props}></Icon>
