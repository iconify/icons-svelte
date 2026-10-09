<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_2bgsjqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d_2bgsjqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cursor-click-48-bold" {...props}></Icon>
