<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_t41-uxm.css';
import '../../css/z/zn2buv2un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g_t41-uxm"/><path class="zn2buv2un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-ui" {...props}></Icon>
