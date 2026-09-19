<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3btvb10h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="j3btvb10h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cube-five" {...props}></Icon>
