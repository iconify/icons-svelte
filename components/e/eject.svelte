<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fp98u-k9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fp98u-k9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:eject" {...props}></Icon>
