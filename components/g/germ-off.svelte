<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp9f0x88f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp9f0x88f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:germ-off" {...props}></Icon>
