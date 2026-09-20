<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ov4w-vcsn.css';
import '../../css/t/t9a55g_zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ov4w-vcsn"/><path class="t9a55g_zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-json-open" {...props}></Icon>
