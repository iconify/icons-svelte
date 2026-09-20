<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyv5sjoyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyv5sjoyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-camera-24" {...props}></Icon>
