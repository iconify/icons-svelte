<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0en2k76l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p0en2k76l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:rooms-storage" {...props}></Icon>
