<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/we18llb1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="we18llb1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:magnet-fill" {...props}></Icon>
