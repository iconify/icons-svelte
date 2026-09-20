<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zafcfcfls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zafcfcfls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:kde-neon" {...props}></Icon>
