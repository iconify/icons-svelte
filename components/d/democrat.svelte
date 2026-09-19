<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf56pcb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kf56pcb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:democrat" {...props}></Icon>
