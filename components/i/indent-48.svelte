<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0pce5fyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="z0pce5fyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:indent-48" {...props}></Icon>
