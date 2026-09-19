<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3g6p4btc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="y3g6p4btc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:one-third-rotation" {...props}></Icon>
