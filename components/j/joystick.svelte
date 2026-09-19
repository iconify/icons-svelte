<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dix5l05ml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dix5l05ml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:joystick" {...props}></Icon>
