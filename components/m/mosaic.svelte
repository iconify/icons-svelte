<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtry4db9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mtry4db9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:mosaic" {...props}></Icon>
