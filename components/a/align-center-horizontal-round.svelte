<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zyt6-xbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zyt6-xbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:align-center-horizontal-round" {...props}></Icon>
