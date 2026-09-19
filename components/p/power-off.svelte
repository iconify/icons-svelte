<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q1s11_vmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="q1s11_vmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:power-off" {...props}></Icon>
