<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr0yipbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wr0yipbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:exe" {...props}></Icon>
