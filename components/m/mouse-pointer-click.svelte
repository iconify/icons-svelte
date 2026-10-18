<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s46w8jbmn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s46w8jbmn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:mouse-pointer-click" {...props}></Icon>
