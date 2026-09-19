<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8_pid-oz.css';
import '../../css/k/klixw6blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="klixw6blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bold" {...props}></Icon>
