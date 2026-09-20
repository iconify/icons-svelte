<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nexjmib3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nexjmib3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:music-slider2" {...props}></Icon>
