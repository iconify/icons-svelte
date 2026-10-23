<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z45_lubjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z45_lubjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:message-square-share" {...props}></Icon>
