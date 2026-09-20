<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yjv321_of.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yjv321_of"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:refresh-circle3-filled" {...props}></Icon>
