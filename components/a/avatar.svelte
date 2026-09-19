<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inucywb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="inucywb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:avatar" {...props}></Icon>
