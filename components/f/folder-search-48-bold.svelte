<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx3v-fbjr.css';
import '../../css/v/v3vwc3z2u.css';
import '../../css/z/zzhfcob3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hx3v-fbjr"/><path class="v3vwc3z2u"/><path class="zzhfcob3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:folder-search-48-bold" {...props}></Icon>
