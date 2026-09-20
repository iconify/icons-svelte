<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s071-i2ck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s071-i2ck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:hexagon" {...props}></Icon>
