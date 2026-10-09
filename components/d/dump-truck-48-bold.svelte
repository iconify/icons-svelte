<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axlm26blc.css';
import '../../css/t/taruh-bis.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="axlm26blc"/><path class="taruh-bis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dump-truck-48-bold" {...props}></Icon>
