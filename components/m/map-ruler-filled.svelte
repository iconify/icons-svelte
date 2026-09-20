<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdd20qqvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdd20qqvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:map-ruler-filled" {...props}></Icon>
