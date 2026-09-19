<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sk2k54bcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sk2k54bcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-message-x" {...props}></Icon>
