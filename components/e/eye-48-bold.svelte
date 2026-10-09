<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybb_vebim.css';
import '../../css/w/wdaa5te7j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ybb_vebim"/><path class="wdaa5te7j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:eye-48-bold" {...props}></Icon>
