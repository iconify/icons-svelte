<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpamcyuwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="lpamcyuwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:drag" {...props}></Icon>
