<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiq-_lbxp.css';
import '../../css/j/j0xfjhbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiq-_lbxp"/><path class="j0xfjhbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-information-2-filled" {...props}></Icon>
