<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybk7p_byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ybk7p_byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:castle-7-filled" {...props}></Icon>
