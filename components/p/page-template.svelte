<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl-k7xb2y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hl-k7xb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:page-template" {...props}></Icon>
