<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vao4db3gf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vao4db3gf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:palette-filled" {...props}></Icon>
