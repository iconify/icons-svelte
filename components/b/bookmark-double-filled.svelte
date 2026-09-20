<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cza95wglm.css';
import '../../css/m/mrmylhbxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cza95wglm"/><path class="mrmylhbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:bookmark-double-filled" {...props}></Icon>
