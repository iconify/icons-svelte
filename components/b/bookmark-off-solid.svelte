<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxevnnfbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxevnnfbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:bookmark-off-solid" {...props}></Icon>
