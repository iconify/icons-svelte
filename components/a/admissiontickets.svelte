<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rp64embkk.css';
import '../../css/i/i6zzx6b9n.css';
import '../../css/a/a56cl1b3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rp64embkk"/><path class="i6zzx6b9n"/><path class="a56cl1b3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:admissiontickets" {...props}></Icon>
