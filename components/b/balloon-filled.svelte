<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox_ew8r3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox_ew8r3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:balloon-filled" {...props}></Icon>
