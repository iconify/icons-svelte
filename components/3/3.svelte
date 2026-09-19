<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q419ru8nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":320,"height":512};
const content = `<path class="q419ru8nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:3" {...props}></Icon>
