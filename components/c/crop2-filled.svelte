<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmkrp6p4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mmkrp6p4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:crop2-filled" {...props}></Icon>
