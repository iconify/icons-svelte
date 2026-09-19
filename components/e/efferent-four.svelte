<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grf5u8f1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="grf5u8f1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:efferent-four" {...props}></Icon>
