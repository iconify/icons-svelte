<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s83cy2i3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="s83cy2i3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:database-outline" {...props}></Icon>
