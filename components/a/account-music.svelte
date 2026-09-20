<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r42o0bbcj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r42o0bbcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:account-music" {...props}></Icon>
