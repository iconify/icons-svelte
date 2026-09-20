<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dahmwgaew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dahmwgaew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-up-circle-filled" {...props}></Icon>
