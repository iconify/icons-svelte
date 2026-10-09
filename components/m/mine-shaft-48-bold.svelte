<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt37rybne.css';
import '../../css/t/tpzkgwbum.css';
import '../../css/v/vargdwkro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vt37rybne"/><path class="tpzkgwbum"/><path class="vargdwkro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:mine-shaft-48-bold" {...props}></Icon>
