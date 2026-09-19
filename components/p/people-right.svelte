<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ce08mxb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ce08mxb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:people-right" {...props}></Icon>
