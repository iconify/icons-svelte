<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8dcjwbei.css';
import '../../css/d/di5phmx8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b x8dcjwbei"/><path class="b di5phmx8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-alt-filled" {...props}></Icon>
