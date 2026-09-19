<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yx-tjbcgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yx-tjbcgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:filter" {...props}></Icon>
