<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sd5t267ma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sd5t267ma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bedside" {...props}></Icon>
