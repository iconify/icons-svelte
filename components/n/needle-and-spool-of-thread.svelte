<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-agpl5uh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r-agpl5uh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:needle-and-spool-of-thread" {...props}></Icon>
