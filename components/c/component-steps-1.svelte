<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gga6pngkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gga6pngkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:component-steps-1" {...props}></Icon>
