<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpblfybed.css';
import '../../css/u/usk21pbsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tpblfybed"/><path class="usk21pbsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:acorn-48-bold" {...props}></Icon>
