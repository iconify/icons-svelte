<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2sjwohsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2sjwohsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:music" {...props}></Icon>
