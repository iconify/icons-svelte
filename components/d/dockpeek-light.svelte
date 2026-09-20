<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hsi_di3ke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hsi_di3ke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:dockpeek-light" {...props}></Icon>
