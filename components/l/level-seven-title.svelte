<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sze5vjbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sze5vjbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:level-seven-title" {...props}></Icon>
