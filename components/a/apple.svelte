<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-6326bns.css';
import '../../css/h/h2clnuigs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s-6326bns"/><path class="h2clnuigs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:apple" {...props}></Icon>
