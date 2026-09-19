<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1k_3abfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="l1k_3abfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:arrow-right" {...props}></Icon>
