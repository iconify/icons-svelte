<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdmzqfeyj.css';
import '../../css/z/zt3xb3pls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wdmzqfeyj"/><path class="zt3xb3pls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:file-search-filled" {...props}></Icon>
