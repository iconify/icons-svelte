<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qgzdi_vdo.css';
import '../../css/w/wfeynzbws.css';
import '../../css/r/rg22j5bgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qgzdi_vdo"/><path class="wfeynzbws"/><path class="rg22j5bgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cabin-48" {...props}></Icon>
