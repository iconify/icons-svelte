<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6la5eb9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p6la5eb9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:api" {...props}></Icon>
