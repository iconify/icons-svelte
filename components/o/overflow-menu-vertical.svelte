<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssbjp9b9f.css';
import '../../css/e/e39ud6bwf.css';
import '../../css/n/nge6tfbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="ssbjp9b9f"/><circle class="e39ud6bwf"/><circle class="nge6tfbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:overflow-menu-vertical" {...props}></Icon>
