<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rs2mikx-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="rs2mikx-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mode-dark-filled" {...props}></Icon>
