<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aylyh4brw.css';
import '../../css/m/m6x3_sbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="aylyh4brw"/><path class="m6x3_sbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-svg-open" {...props}></Icon>
