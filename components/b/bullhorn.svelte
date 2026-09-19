<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgdq4zzsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rgdq4zzsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:bullhorn" {...props}></Icon>
