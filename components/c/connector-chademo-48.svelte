<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg-biwbzh.css';
import '../../css/h/h1lg0z1zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xg-biwbzh"/><path class="h1lg0z1zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:connector-chademo-48" {...props}></Icon>
