<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwsi43bkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwsi43bkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:fill-color-1-filled" {...props}></Icon>
