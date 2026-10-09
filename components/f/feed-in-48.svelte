<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/friknfboq.css';
import '../../css/v/v3-yombvq.css';
import '../../css/v/v403anbqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="friknfboq"/><path class="v3-yombvq"/><path class="v403anbqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:feed-in-48" {...props}></Icon>
