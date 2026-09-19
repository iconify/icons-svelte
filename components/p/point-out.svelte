<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xar2vs8av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xar2vs8av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:point-out" {...props}></Icon>
