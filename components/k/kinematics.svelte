<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/irwj-e5bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="irwj-e5bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:kinematics" {...props}></Icon>
