<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dp42yhc0n.css';
import '../../css/m/mrws6bc9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dp42yhc0n"/><path class="mrws6bc9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hacksaw-20-bold" {...props}></Icon>
