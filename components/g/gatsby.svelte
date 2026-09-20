<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ralofz4_e.css';
import '../../css/k/ke769lv4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":28};
const content = `<path class="ralofz4_e"/><path class="ke769lv4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:gatsby" {...props}></Icon>
