<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzrk6-7wu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gzrk6-7wu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:off-screen-two" {...props}></Icon>
