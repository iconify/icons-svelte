<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8nk-ib1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p8nk-ib1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dot" {...props}></Icon>
