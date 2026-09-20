<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ulas4swoq.css';
import '../../css/p/pxb9n0nrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ulas4swoq"/><path class="pxb9n0nrg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-cursor-open" {...props}></Icon>
