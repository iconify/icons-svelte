<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3d3babjk.css';
import '../../css/o/owcw62b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m3d3babjk"/><path class="owcw62b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hand-rock-filled" {...props}></Icon>
