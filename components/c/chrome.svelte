<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9vdcnbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p9vdcnbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:chrome" {...props}></Icon>
