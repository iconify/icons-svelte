<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6p-n4b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e6p-n4b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:off-screen" {...props}></Icon>
