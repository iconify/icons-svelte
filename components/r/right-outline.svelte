<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf8p51b2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bf8p51b2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:right-outline" {...props}></Icon>
