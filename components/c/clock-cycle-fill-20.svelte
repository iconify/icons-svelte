<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5knpcbeg.css';
import '../../css/r/rqr606bgh.css';
import '../../css/t/t3muc1b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e5knpcbeg"/><path class="rqr606bgh"/><path class="t3muc1b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-cycle-fill-20" {...props}></Icon>
