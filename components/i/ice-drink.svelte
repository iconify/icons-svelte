<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sim-79wsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="sim-79wsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:ice-drink" {...props}></Icon>
