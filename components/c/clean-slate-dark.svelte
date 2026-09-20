<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp195kbkj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kp195kbkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:clean-slate-dark" {...props}></Icon>
