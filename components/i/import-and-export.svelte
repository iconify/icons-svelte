<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qetzpaczm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qetzpaczm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:import-and-export" {...props}></Icon>
