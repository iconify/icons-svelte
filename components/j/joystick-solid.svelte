<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/twadonbqo.css';
import '../../css/u/umps_z5qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="twadonbqo"/><path class="umps_z5qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:joystick-solid" {...props}></Icon>
