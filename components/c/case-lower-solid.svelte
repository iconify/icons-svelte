<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl64idgpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl64idgpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:case-lower-solid" {...props}></Icon>
