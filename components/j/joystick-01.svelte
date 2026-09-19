<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n03bg7bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n03bg7bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:joystick-01" {...props}></Icon>
