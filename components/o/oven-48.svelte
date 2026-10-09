<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co-y23bkw.css';
import '../../css/a/aui1l8ddh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="co-y23bkw"/><path class="aui1l8ddh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oven-48" {...props}></Icon>
