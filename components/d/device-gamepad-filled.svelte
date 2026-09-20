<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4brmzjgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4brmzjgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-gamepad-filled" {...props}></Icon>
