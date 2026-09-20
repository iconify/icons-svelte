<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbic-tukd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbic-tukd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:pending-filled" {...props}></Icon>
